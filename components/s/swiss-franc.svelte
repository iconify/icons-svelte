<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_ab_21tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ab_21tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:swiss-franc" {...props}></Icon>
