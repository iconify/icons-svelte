<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmnaz41ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pmnaz41ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:schneiderelectric" {...props}></Icon>
