<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wq_pzdluz.css';
import '../../css/s/sp9gcvbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wq_pzdluz"/><path class="sp9gcvbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:video-edit-cut-bold" {...props}></Icon>
