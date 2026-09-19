<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa3zcxb8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa3zcxb8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:shield-person-filled" {...props}></Icon>
