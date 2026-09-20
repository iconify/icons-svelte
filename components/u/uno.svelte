<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9dp65n1d.css';
import '../../css/t/tqpzs3bol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9dp65n1d"/><path class="tqpzs3bol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:uno" {...props}></Icon>
