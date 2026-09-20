<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/or0_-7bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="or0_-7bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:rye" {...props}></Icon>
