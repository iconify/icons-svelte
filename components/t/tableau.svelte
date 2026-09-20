<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jxmt3hbix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jxmt3hbix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tableau" {...props}></Icon>
