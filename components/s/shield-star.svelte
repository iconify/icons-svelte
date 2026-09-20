<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enjd4q_it.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="enjd4q_it"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:shield-star" {...props}></Icon>
