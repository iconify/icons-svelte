<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovu3qlb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovu3qlb7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:streamlit" {...props}></Icon>
