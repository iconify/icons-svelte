<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb-4zccna.css';
import '../../css/y/ypq-gib4v.css';
import '../../css/s/s29qprbza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nb-4zccna"/><path clip-rule="evenodd" class="ypq-gib4v"/><path clip-rule="evenodd" class="s29qprbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:visibility-off-outline" {...props}></Icon>
