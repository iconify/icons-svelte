<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdftbpbaj.css';
import '../../css/m/m26ewvbtd.css';
import '../../css/g/gw6wfjnqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="wdftbpbaj"/><path class="m26ewvbtd"/><path class="gw6wfjnqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:turkey" {...props}></Icon>
