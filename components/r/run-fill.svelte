<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4lk5fbgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4lk5fbgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:run-fill" {...props}></Icon>
