<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezdp1hbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ezdp1hbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:tune-horizontal-alt" {...props}></Icon>
