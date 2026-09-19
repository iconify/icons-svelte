<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi1tfvbwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xi1tfvbwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:trash-cancel" {...props}></Icon>
