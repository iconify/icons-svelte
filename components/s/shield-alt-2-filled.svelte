<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ih0i_2fow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih0i_2fow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shield-alt-2-filled" {...props}></Icon>
