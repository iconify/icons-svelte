<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkqq6fire.css';
import '../../css/u/ulrix6h0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lkqq6fire"/><path class="ulrix6h0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:text-format-bold" {...props}></Icon>
