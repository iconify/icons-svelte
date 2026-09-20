<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kl964s_ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kl964s_ee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:the-movie-database" {...props}></Icon>
