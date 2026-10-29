<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ui0ttgbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ui0ttgbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:store-solid" {...props}></Icon>
