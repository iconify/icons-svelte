<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk0s61b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fk0s61b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:settings-adjust-horizontal-filled" {...props}></Icon>
