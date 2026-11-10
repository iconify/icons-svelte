<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1tp18z4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d1tp18z4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:user-x-mark" {...props}></Icon>
