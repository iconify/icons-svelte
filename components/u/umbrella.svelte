<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aj-hdumnn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aj-hdumnn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:umbrella" {...props}></Icon>
