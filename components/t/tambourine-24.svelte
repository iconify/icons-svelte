<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojxt9lbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojxt9lbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:tambourine-24" {...props}></Icon>
