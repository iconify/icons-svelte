<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co0uccbji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co0uccbji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:user-minus-fill" {...props}></Icon>
