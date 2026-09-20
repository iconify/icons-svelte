<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hll8w5bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hll8w5bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sun-medium" {...props}></Icon>
