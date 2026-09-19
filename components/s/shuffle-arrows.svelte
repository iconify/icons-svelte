<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk2t5mbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="yk2t5mbjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:shuffle-arrows" {...props}></Icon>
