<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv99crk7v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv99crk7v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rust" {...props}></Icon>
