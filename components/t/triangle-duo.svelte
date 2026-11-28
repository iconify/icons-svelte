<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/id5i4irup.css';
import '../../css/q/qi6vm4w9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="id5i4irup secondary"/><path class="primary qi6vm4w9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:triangle-duo" {...props}></Icon>
