<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0i3lilqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g0i3lilqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:user-check" {...props}></Icon>
