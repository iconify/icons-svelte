<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gz9y9syrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gz9y9syrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:voicemail" {...props}></Icon>
