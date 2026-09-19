<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_v_5prdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_v_5prdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sunrise" {...props}></Icon>
