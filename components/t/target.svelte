<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qncohgb7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qncohgb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:target" {...props}></Icon>
