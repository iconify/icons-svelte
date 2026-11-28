<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fan6-n1tt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fan6-n1tt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:zoom-out-solid" {...props}></Icon>
