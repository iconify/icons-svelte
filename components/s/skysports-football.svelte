<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5ohjybjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u5ohjybjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:skysports-football" {...props}></Icon>
