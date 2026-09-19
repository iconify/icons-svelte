<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukooq9bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ukooq9bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:waning-crescent-moon-symbol" {...props}></Icon>
