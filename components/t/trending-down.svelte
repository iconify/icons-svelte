<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/afs_3s29k.css';
import '../../css/g/gp4srle1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="afs_3s29k"/><path class="gp4srle1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:trending-down" {...props}></Icon>
