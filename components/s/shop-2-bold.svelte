<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu28wccgh.css';
import '../../css/z/zfnhitbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wu28wccgh"/><path class="zfnhitbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shop-2-bold" {...props}></Icon>
