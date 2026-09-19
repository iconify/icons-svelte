<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fse9x8baa.css';
import '../../css/d/dlp7nstpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fse9x8baa"/><circle class="dlp7nstpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:server-dns" {...props}></Icon>
