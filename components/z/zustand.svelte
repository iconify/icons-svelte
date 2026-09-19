<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6quybcki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a6quybcki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:zustand" {...props}></Icon>
