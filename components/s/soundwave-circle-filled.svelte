<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2sn25lun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v2sn25lun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:soundwave-circle-filled" {...props}></Icon>
