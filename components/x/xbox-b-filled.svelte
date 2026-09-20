<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_baw7aur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_baw7aur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:xbox-b-filled" {...props}></Icon>
