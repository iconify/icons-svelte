<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/teizhzbmj.css';
import '../../css/l/lx8hjcc6o.css';
import '../../css/n/nceqg5bzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="teizhzbmj"/><path class="lx8hjcc6o"/><path class="nceqg5bzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:taking-pictures-cameras-bold" {...props}></Icon>
