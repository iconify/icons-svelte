<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hknrkvh-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hknrkvh-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ruler4-filled" {...props}></Icon>
