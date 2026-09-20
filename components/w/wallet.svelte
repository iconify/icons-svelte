<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t8-0jeb9m.css';
import '../../css/o/o_2dpvb9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t8-0jeb9m"/><path class="o_2dpvb9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:wallet" {...props}></Icon>
