<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fkh1hqb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fkh1hqb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:shadows" {...props}></Icon>
