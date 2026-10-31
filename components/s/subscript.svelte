<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/e/e5qwh6ble.css';
import '../../css/v/vyut8oaub.css';
import '../../css/p/pkb4u5hql.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="e5qwh6ble wm-shadow"/><path class="vyut8oaub wm-shadow"/><path class="pkb4u5hql"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:subscript" {...props}></Icon>
