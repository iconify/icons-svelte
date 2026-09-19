<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsngwqb7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="hsngwqb7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:t-v-monitor" {...props}></Icon>
