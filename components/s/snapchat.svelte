<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9hdpufda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":24};
const content = `<path class="v9hdpufda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:snapchat" {...props}></Icon>
