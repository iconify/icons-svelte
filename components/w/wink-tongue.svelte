<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xe03g2-dk.css';
import '../../css/i/igs44wb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xe03g2-dk"/><path class="igs44wb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wink-tongue" {...props}></Icon>
