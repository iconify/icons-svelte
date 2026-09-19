<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2zxg1bax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j2zxg1bax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-crack-filled" {...props}></Icon>
