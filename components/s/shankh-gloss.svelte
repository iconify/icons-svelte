<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6ol74bqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6ol74bqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shankh-gloss" {...props}></Icon>
