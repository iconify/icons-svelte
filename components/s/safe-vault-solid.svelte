<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgkd6e21x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fgkd6e21x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:safe-vault-solid" {...props}></Icon>
