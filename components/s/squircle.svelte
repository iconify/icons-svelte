<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ii2_-nb_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ii2_-nb_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:squircle" {...props}></Icon>
