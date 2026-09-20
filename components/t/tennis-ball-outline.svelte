<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui42f08vj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui42f08vj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:tennis-ball-outline" {...props}></Icon>
