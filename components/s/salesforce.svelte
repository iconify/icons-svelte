<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlcme2bry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="qlcme2bry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:salesforce" {...props}></Icon>
