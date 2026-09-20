<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpsyw0ehr.css';
import '../../css/i/io_v3whei.css';
import '../../css/s/sn4d4xbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xpsyw0ehr"/><path class="io_v3whei"/><path class="sn4d4xbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:whodb-dark" {...props}></Icon>
