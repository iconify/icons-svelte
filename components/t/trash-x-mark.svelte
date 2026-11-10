<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ygrqq9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9ygrqq9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:trash-x-mark" {...props}></Icon>
