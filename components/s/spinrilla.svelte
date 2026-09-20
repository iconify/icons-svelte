<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv6r48b_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv6r48b_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:spinrilla" {...props}></Icon>
