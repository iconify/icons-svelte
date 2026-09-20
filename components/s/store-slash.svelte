<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k__cg03cc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k__cg03cc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:store-slash" {...props}></Icon>
