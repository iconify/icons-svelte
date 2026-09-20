<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1od96_bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1od96_bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:trello-line" {...props}></Icon>
