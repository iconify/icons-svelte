<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isuqlx49y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isuqlx49y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-minimalistic-linear" {...props}></Icon>
