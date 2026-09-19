<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1mwf5jar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1mwf5jar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tooth-gum-inflammation" {...props}></Icon>
