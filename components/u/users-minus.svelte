<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe6a_3byp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oe6a_3byp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:users-minus" {...props}></Icon>
