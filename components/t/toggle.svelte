<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3eha7bzt.css';
import '../../css/r/r3a3c2hpl.css';
import '../../css/w/w5ou4mocx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3eha7bzt wm-k"/><path class="r3a3c2hpl wm-a"/><path class="w5ou4mocx wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:toggle" {...props}></Icon>
