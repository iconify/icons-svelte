<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_1x8qb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_1x8qb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:tag-solid" {...props}></Icon>
