<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdw3bhb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdw3bhb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:trending-down" {...props}></Icon>
