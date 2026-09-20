<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b-k3q1bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b-k3q1bfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:trakt" {...props}></Icon>
