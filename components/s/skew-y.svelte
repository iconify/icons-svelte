<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugsr7ob4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugsr7ob4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:skew-y" {...props}></Icon>
