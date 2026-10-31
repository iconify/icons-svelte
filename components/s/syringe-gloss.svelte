<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq6od-5yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bq6od-5yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:syringe-gloss" {...props}></Icon>
