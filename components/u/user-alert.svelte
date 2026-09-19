<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5s6a10qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5s6a10qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:user-alert" {...props}></Icon>
