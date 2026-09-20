<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/updm7mb5b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="updm7mb5b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:saxophone-24" {...props}></Icon>
