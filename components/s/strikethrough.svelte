<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edv__jq6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edv__jq6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:strikethrough" {...props}></Icon>
