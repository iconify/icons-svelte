<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s63tnf0jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s63tnf0jh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:shield-half-filled" {...props}></Icon>
