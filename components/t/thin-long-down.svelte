<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg6wyobjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg6wyobjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:thin-long-down" {...props}></Icon>
