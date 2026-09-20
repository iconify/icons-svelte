<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-k_f2b7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s-k_f2b7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:security-user-filled" {...props}></Icon>
