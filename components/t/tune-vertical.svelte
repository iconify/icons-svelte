<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru19-jbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ru19-jbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tune-vertical" {...props}></Icon>
