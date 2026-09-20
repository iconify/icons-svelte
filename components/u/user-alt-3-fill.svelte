<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rop6in0iw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rop6in0iw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:user-alt-3-fill" {...props}></Icon>
