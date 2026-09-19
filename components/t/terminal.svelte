<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xa7zqbbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xa7zqbbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:terminal" {...props}></Icon>
