<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esumcwhah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="esumcwhah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:shopping-bag" {...props}></Icon>
