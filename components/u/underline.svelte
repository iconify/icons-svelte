<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8t4q31pr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8t4q31pr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:underline" {...props}></Icon>
