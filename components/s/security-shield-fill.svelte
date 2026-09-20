<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lxy4-i9_f.css';
import '../../css/t/tbnr6-0gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lxy4-i9_f"/><path class="tbnr6-0gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:security-shield-fill" {...props}></Icon>
