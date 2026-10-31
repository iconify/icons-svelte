<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avaz35vcl.css';
import '../../css/d/d6irxobcr.css';
import '../../css/s/s9f_vlb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="avaz35vcl"/><path class="d6irxobcr"/><path class="s9f_vlb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:turkmenistan" {...props}></Icon>
