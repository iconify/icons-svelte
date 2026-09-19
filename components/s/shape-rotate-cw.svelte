<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx3-ah38a.css';
import '../../css/g/gjzjcyb6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b tx3-ah38a"/><path class="b gjzjcyb6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shape-rotate-cw" {...props}></Icon>
