<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atig-hh7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="atig-hh7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:wpressr" {...props}></Icon>
