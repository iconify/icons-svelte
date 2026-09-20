<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0z2e2bxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x0z2e2bxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:wantedly" {...props}></Icon>
