<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sw4lg9bbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sw4lg9bbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:westerndigital" {...props}></Icon>
