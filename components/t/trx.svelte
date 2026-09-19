<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ym3v0_fpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ym3v0_fpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:trx" {...props}></Icon>
