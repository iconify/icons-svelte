<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iht6zqb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iht6zqb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:soup" {...props}></Icon>
