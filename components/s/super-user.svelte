<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpape142n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kpape142n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:super-user" {...props}></Icon>
