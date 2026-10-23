<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq0w-2bco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq0w-2bco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:sunset" {...props}></Icon>
