<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puw0kjb1k.css';
import '../../css/g/ginn57b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="puw0kjb1k"/><path class="ginn57b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rounded-magnifer-bug-bold" {...props}></Icon>
