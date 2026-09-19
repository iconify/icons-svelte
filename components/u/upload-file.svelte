<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmwpenbhg.css';
import '../../css/i/i4bpspa_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer pmwpenbhg"/><path class="duoicon-primary-layer i4bpspa_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:upload-file" {...props}></Icon>
