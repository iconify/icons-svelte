<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6fwl2bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t6fwl2bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shield-check" {...props}></Icon>
