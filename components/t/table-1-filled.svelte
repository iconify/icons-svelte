<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkxs0px9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkxs0px9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:table-1-filled" {...props}></Icon>
