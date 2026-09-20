<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz6c57d1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xz6c57d1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-x-filled" {...props}></Icon>
