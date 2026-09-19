<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9pgq_bag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9pgq_bag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:store-filled" {...props}></Icon>
