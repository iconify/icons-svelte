<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9yfjzbsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s9yfjzbsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:sofa-filled" {...props}></Icon>
