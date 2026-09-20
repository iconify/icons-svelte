<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsse1acur.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsse1acur"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:tensorflow" {...props}></Icon>
