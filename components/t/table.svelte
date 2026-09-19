<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcu6m8bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zcu6m8bip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:table" {...props}></Icon>
