<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_vo2cbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_vo2cbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:square-chevron-down-filled" {...props}></Icon>
