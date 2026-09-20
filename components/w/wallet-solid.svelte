<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byzi3kb5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="byzi3kb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:wallet-solid" {...props}></Icon>
