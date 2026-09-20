<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nhtk0wbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nhtk0wbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uis:sync-slash" {...props}></Icon>
