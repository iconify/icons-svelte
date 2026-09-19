<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmqi-0gnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":497,"height":667};
const content = `<path class="pmqi-0gnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:v" {...props}></Icon>
