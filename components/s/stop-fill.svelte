<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_ny3m6cp.css';
import '../../css/z/z_8t63-wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="f_ny3m6cp"/><rect class="z_8t63-wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:stop-fill" {...props}></Icon>
