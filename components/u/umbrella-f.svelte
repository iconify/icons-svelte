<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iad7h8ttc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="iad7h8ttc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:umbrella-f" {...props}></Icon>
