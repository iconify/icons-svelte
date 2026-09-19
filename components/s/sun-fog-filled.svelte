<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2j8i59bg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o2j8i59bg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:sun-fog-filled" {...props}></Icon>
