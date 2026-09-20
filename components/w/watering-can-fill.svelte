<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b68sjcc4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b68sjcc4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:watering-can-fill" {...props}></Icon>
