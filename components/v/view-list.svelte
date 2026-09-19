<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcm6aifgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcm6aifgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:view-list" {...props}></Icon>
