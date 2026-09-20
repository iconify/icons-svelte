<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hct-yyznp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hct-yyznp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:trakt-dark" {...props}></Icon>
