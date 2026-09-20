<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc8rkpbcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kc8rkpbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:user-sync-online-in-person-solid" {...props}></Icon>
