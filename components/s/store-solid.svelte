<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofzsp5buw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofzsp5buw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:store-solid" {...props}></Icon>
