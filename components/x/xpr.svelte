<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddkpy6xif.css';
import '../../css/k/kxukhz28t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddkpy6xif"/><path class="kxukhz28t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:xpr" {...props}></Icon>
